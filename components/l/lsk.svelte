<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6oc-mbql.css';
import '../../css/x/x4ukzbcus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6oc-mbql"/><path class="x4ukzbcus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lsk" {...props}></Icon>
