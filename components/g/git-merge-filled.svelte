<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwe_18keh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwe_18keh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:git-merge-filled" {...props}></Icon>
