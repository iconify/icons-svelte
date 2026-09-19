<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq_pp9coz.css';
import '../../css/v/vslt2rbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer vq_pp9coz"/><path class="duoicon-primary-layer vslt2rbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:credit-card" {...props}></Icon>
