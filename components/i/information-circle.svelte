<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxa_h81tv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxa_h81tv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:information-circle" {...props}></Icon>
