<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ampx37alc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ampx37alc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ha-blue" {...props}></Icon>
