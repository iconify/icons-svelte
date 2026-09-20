<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4otdk7by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="h4otdk7by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-boarding-taxi" {...props}></Icon>
