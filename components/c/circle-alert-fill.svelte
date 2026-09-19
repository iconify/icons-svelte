<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4v-e7urh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x4v-e7urh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:circle-alert-fill" {...props}></Icon>
