<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t19_d8l-n.css';
import '../../css/u/u7aldsb5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t19_d8l-n"/><path class="u7aldsb5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:last-updates" {...props}></Icon>
