<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlqrl5bli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlqrl5bli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:attachment-alt-02" {...props}></Icon>
