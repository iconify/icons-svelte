<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m21xs_4fm.css';
import '../../css/u/u3htxq4vz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m21xs_4fm"/><path class="u3htxq4vz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:humidifier-20" {...props}></Icon>
