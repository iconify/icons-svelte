<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvnsb8bex.css';
import '../../css/r/rjfhlsb4c.css';
import '../../css/o/o235c4b9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dvnsb8bex"/><path class="rjfhlsb4c"/><path class="o235c4b9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:android-os" {...props}></Icon>
