<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq0eybcdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vq0eybcdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:face-id-solid" {...props}></Icon>
