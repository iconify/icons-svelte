<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j84coq6et.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j84coq6et"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ara-records-ansible-light" {...props}></Icon>
