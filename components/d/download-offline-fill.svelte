<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9lrsebuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n9lrsebuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:download-offline-fill" {...props}></Icon>
