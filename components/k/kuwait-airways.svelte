<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9g34x91z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9g34x91z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:kuwait-airways" {...props}></Icon>
