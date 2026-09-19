<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/q0q3_db9v.css';
import '../../css/z/z9_ovrbwf.css';
import '../../css/c/c7xazyb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="q0q3_db9v"/><path clip-rule="evenodd" class="z9_ovrbwf"/><path class="c7xazyb5c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:password-cursor" {...props}></Icon>
