<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o26-z7b6y.css';
import '../../css/c/c4z6olb-l.css';
import '../../css/s/see0y-btr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o26-z7b6y"/><path class="c4z6olb-l"/><path class="see0y-btr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:imbalance-48-bold" {...props}></Icon>
