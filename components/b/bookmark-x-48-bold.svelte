<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c45xl7zgy.css';
import '../../css/h/hwjgqrbah.css';
import '../../css/s/sfb8rqn9v.css';
import '../../css/k/ksydp3lsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c45xl7zgy"/><path class="hwjgqrbah"/><path class="sfb8rqn9v"/><path class="ksydp3lsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bookmark-x-48-bold" {...props}></Icon>
