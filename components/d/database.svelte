<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zshnz-zog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zshnz-zog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:database" {...props}></Icon>
