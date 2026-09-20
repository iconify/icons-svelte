<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/g/g1xg7eiii.css';
import '../../css/g/gzw7gyr6o.css';
import '../../css/s/s1z0bh-al.css';
import '../../css/n/nqy-9n9qs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g1xg7eiii"/><path class="gzw7gyr6o"/><path class="s1z0bh-al"/><path class="nqy-9n9qs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cards" {...props}></Icon>
