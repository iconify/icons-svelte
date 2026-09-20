<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epa1joxjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="epa1joxjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jfa-go-light" {...props}></Icon>
