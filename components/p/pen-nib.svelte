<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt2o9cczv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wt2o9cczv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:pen-nib" {...props}></Icon>
