<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_29zdb8m.css';
import '../../css/a/a6-juwioy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_29zdb8m"/><path clip-rule="evenodd" class="a6-juwioy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:calendar-add-bold" {...props}></Icon>
