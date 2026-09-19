<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsb8ijb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vsb8ijb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:ocaml" {...props}></Icon>
