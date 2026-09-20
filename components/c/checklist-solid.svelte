<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_70c4b5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_70c4b5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:checklist-solid" {...props}></Icon>
