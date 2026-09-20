<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3qp6x1gw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3qp6x1gw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:play" {...props}></Icon>
