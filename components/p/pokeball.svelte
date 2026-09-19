<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4zs08s-q.css';
import '../../css/j/jx0p4fbya.css';
import '../../css/b/b2c0qprhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGOFGrfdbi" class="g4zs08s-q"/></defs><g class="jx0p4fbya"><use href="#SVGOFGrfdbi"/><use href="#SVGOFGrfdbi"/><path class="b2c0qprhd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pokeball" {...props}></Icon>
