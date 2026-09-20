<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beg17-bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="beg17-bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-down-left-sharp-fill" {...props}></Icon>
