<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onyo9ll8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="onyo9ll8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:osmand" {...props}></Icon>
