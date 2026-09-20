<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3qp6x1gw.css';
import '../../css/c/cg710qboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3qp6x1gw"/><path class="cg710qboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:play-duotone" {...props}></Icon>
