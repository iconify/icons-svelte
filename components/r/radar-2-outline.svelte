<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9h39ibto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h9h39ibto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:radar-2-outline" {...props}></Icon>
