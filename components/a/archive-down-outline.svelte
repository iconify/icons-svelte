<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szapj5bkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="szapj5bkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-down-outline" {...props}></Icon>
