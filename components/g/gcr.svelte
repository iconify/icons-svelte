<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8z545b6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v8z545b6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:gcr" {...props}></Icon>
