<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzs5177np.css';
import '../../css/j/jmz-_09oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fzs5177np"/><path class="jmz-_09oz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-heart-20" {...props}></Icon>
