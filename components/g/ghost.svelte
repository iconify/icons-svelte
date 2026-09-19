<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqfno6r6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nqfno6r6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:ghost" {...props}></Icon>
