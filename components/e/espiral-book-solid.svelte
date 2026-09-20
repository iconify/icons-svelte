<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq3zk27rk.css';
import '../../css/h/hlp216lkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qq3zk27rk"/><path class="hlp216lkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:espiral-book-solid" {...props}></Icon>
