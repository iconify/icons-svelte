<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iauax3bdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iauax3bdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:burj-al-arab-fill" {...props}></Icon>
