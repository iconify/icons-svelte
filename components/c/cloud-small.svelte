<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eee2krb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":10};
const content = `<path class="eee2krb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:cloud-small" {...props}></Icon>
