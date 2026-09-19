<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls4d_78wt.css';
import '../../css/z/z6z042bmd.css';
import '../../css/a/a-zsnuk-t.css';
import '../../css/w/wx0qoilek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ls4d_78wt"/><path class="z6z042bmd"/><path class="a-zsnuk-t"/><path class="wx0qoilek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:qr-code-sharp" {...props}></Icon>
