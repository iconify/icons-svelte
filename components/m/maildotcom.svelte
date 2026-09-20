<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guc0uebjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="guc0uebjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:maildotcom" {...props}></Icon>
