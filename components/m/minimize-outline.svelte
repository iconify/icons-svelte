<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doex5ofaj.css';
import '../../css/o/om-12ci7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="doex5ofaj"/><path class="om-12ci7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:minimize-outline" {...props}></Icon>
