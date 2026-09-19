<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_dmztt_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_dmztt_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:exclaimation-circle" {...props}></Icon>
