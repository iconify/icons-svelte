<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6odt7b8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6odt7b8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pen-alt" {...props}></Icon>
