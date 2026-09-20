<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-ju2fxdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-ju2fxdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:more-horiz-line" {...props}></Icon>
