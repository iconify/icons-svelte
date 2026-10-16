<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6fk-hbzz.css';
import '../../css/h/h92n3z2qg.css';
import '../../css/i/im5n_6bkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l6fk-hbzz"/><path class="h92n3z2qg"/><path class="im5n_6bkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:oil-tanker-48-bold" {...props}></Icon>
