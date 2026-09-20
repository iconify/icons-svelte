<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz6a-wbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hz6a-wbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:amazonelasticache" {...props}></Icon>
