<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhw43hs6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dhw43hs6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:profile-card-solid" {...props}></Icon>
