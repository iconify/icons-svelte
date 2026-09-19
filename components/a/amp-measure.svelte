<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-s3pyccr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-s3pyccr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:amp-measure" {...props}></Icon>
