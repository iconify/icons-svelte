<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wao7fvqjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wao7fvqjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:bolt" {...props}></Icon>
