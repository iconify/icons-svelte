<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3-jnqb4z.css';
import '../../css/c/c7wml7kwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o3-jnqb4z"/><path class="c7wml7kwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:mail-outgoing-solid" {...props}></Icon>
