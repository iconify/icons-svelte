<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7r9geb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7r9geb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:egg-yolk-filled" {...props}></Icon>
