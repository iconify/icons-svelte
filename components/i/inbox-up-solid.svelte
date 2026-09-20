<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx930cc8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nx930cc8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:inbox-up-solid" {...props}></Icon>
