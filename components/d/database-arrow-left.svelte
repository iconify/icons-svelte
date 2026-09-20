<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy1qikb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uy1qikb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-arrow-left" {...props}></Icon>
