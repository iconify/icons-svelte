<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyjz57b0u.css';
import '../../css/h/h124n3njl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="nyjz57b0u"/><path class="h124n3njl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:dovecot" {...props}></Icon>
