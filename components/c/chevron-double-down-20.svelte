<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laonxqbvy.css';
import '../../css/g/gmakb7b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="laonxqbvy"/><path class="gmakb7b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-double-down-20" {...props}></Icon>
