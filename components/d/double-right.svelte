<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwqiqkueu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gwqiqkueu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:double-right" {...props}></Icon>
