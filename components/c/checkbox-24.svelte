<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5ra11bdp.css';
import '../../css/l/lb-bssbki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5ra11bdp"/><path class="lb-bssbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:checkbox-24" {...props}></Icon>
