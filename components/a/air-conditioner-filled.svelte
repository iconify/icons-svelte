<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8z70n3em.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x8z70n3em"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:air-conditioner-filled" {...props}></Icon>
