<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm498ybdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gm498ybdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:expand-dashed-up-left-sharp-fill" {...props}></Icon>
