<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr1ba6b2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="fr1ba6b2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:mobile" {...props}></Icon>
