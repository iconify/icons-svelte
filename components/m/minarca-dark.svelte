<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d12bk8tox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d12bk8tox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:minarca-dark" {...props}></Icon>
