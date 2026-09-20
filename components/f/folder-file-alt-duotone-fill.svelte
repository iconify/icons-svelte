<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lohg0pbwp.css';
import '../../css/v/v5tal47iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lohg0pbwp"/><path class="v5tal47iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:folder-file-alt-duotone-fill" {...props}></Icon>
