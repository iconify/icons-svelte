<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6bs9-bbu.css';
import '../../css/d/dehw9gqms.css';
import '../../css/e/eep2d1vox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m6bs9-bbu"/><path class="dehw9gqms"/><path class="eep2d1vox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:document-add-bold" {...props}></Icon>
