<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um0cmtqka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="um0cmtqka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:redmine-dark" {...props}></Icon>
