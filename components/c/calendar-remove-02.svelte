<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v19_6476u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v19_6476u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:calendar-remove-02" {...props}></Icon>
