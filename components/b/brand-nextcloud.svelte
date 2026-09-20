<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbq-nhb8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbq-nhb8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-nextcloud" {...props}></Icon>
