<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5fu9jbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5fu9jbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:atom-solid" {...props}></Icon>
