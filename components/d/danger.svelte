<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlqqbzuhn.css';
import '../../css/b/b_4q_nb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="mlqqbzuhn"/><path class="b_4q_nb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:danger" {...props}></Icon>
