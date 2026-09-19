<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2qd5b7pd.css';
import '../../css/a/abf4dkbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2qd5b7pd"/><path class="abf4dkbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:moon-stars-filled" {...props}></Icon>
