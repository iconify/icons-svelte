<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdj2bxbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdj2bxbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:chef-hat-filled" {...props}></Icon>
