<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik6frwa0u.css';
import '../../css/i/idgsmsbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ik6frwa0u"/><path class="idgsmsbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:fish" {...props}></Icon>
