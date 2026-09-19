<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9tnq6bdy.css';
import '../../css/k/k9r7cbc0o.css';
import '../../css/g/gojllccbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":13,"height":16};
const content = `<path class="v9tnq6bdy"/><path class="k9r7cbc0o"/><path class="gojllccbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:avatarwoman" {...props}></Icon>
