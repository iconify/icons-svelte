<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqs2meyid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vqs2meyid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:face-laughz-solid" {...props}></Icon>
