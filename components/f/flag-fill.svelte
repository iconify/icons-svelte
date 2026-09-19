<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abjmkbc1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="abjmkbc1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:flag-fill" {...props}></Icon>
