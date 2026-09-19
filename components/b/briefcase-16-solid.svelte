<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii5d476rw.css';
import '../../css/h/hqx9vqk3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ii5d476rw"/><path class="hqx9vqk3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:briefcase-16-solid" {...props}></Icon>
