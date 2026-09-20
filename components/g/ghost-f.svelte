<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdacv0zkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="gdacv0zkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:ghost-f" {...props}></Icon>
