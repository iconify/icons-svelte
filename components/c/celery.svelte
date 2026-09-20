<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrhv5lb3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrhv5lb3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:celery" {...props}></Icon>
