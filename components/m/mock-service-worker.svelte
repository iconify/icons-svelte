<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrm3k6bil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrm3k6bil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mock-service-worker" {...props}></Icon>
