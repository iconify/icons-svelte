<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-4-x7bhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-4-x7bhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-cake" {...props}></Icon>
