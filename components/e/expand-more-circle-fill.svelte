<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge7fm3s-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ge7fm3s-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:expand-more-circle-fill" {...props}></Icon>
