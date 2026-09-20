<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooq5nrwwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ooq5nrwwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:lungs-fill" {...props}></Icon>
