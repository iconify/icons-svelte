<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqm9wbc2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":33,"height":33};
const content = `<path clip-rule="evenodd" class="oqm9wbc2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:okta" {...props}></Icon>
