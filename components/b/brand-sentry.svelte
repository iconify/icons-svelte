<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6wdwzbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6wdwzbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-sentry" {...props}></Icon>
