<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdbs6tbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdbs6tbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:person-running-solid" {...props}></Icon>
