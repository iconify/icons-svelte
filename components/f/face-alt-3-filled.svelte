<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-kbjab1h.css';
import '../../css/a/ao1_d-37i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-kbjab1h"/><path class="ao1_d-37i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:face-alt-3-filled" {...props}></Icon>
