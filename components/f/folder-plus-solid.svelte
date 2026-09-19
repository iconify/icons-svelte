<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhpgkug3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nhpgkug3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:folder-plus-solid" {...props}></Icon>
