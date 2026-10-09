<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g20323bqu.css';
import '../../css/j/jcg7b95lb.css';
import '../../css/y/y-8q6156p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g20323bqu"/><path class="jcg7b95lb"/><path class="y-8q6156p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:factory-emissions-48" {...props}></Icon>
