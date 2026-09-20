<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtat2y9dp.css';
import '../../css/f/f29qyf3ac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="jtat2y9dp"/><path class="f29qyf3ac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:circleci-light" {...props}></Icon>
