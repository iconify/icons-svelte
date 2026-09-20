<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub9sfq3xt.css';
import '../../css/m/mkx79kbti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ub9sfq3xt"/><path class="mkx79kbti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:pencil-writing" {...props}></Icon>
