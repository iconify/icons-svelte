<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp6zpdntm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bp6zpdntm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apache-tomcat-light" {...props}></Icon>
