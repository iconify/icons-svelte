<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0ri6bb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g0ri6bb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:data-cloud-download" {...props}></Icon>
