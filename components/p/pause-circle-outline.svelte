<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmqit-klp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gmqit-klp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pause-circle-outline" {...props}></Icon>
