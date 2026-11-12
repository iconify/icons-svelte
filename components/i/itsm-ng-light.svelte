<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjqtnac9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cjqtnac9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:itsm-ng-light" {...props}></Icon>
