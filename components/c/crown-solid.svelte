<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt73p7fso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dt73p7fso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:crown-solid" {...props}></Icon>
