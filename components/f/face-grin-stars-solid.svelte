<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v16xx8pet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v16xx8pet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:face-grin-stars-solid" {...props}></Icon>
