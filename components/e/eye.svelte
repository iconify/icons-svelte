<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2w8m1bts.css';
import '../../css/s/st6zf__cy.css';
import '../../css/f/fpuu3bcbf.css';
import '../../css/c/czclt8bgq.css';
import '../../css/y/yoa9wypyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c2w8m1bts"/><path class="st6zf__cy"/><path class="fpuu3bcbf"/><path class="czclt8bgq"/><path class="yoa9wypyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:eye" {...props}></Icon>
