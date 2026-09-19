<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/oixycubyj.css';
import '../../css/t/tmbuc6btd.css';
import '../../css/v/vhjlelb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="oixycubyj"/><path class="tmbuc6btd"/><path class="vhjlelb7g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:light-switch-duo" {...props}></Icon>
