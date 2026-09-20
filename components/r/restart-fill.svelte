<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw_83wk5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tw_83wk5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:restart-fill" {...props}></Icon>
