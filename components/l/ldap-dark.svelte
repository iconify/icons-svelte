<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb7olybwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jb7olybwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ldap-dark" {...props}></Icon>
