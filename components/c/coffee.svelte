<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxv5vzupi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxv5vzupi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:coffee" {...props}></Icon>
