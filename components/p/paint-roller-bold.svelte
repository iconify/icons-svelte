<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwit5_4bm.css';
import '../../css/a/a6molq-5v.css';
import '../../css/z/z75ed3b-u.css';
import '../../css/b/b4tox8bhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwit5_4bm"/><path class="a6molq-5v"/><path class="z75ed3b-u"/><path class="b4tox8bhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paint-roller-bold" {...props}></Icon>
