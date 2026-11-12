<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihcuxaciq.css';
import '../../css/h/ho7n6nb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ihcuxaciq"/><path class="ho7n6nb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:espocrm" {...props}></Icon>
