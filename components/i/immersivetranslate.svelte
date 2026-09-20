<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/darj4dbtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="darj4dbtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:immersivetranslate" {...props}></Icon>
